<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/picx5jbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="picx5jbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-left" {...props}></Icon>
