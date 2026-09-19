<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv8if_ohd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv8if_ohd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:flag" {...props}></Icon>
