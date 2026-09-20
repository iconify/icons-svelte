<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds-7gmbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds-7gmbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-up" {...props}></Icon>
