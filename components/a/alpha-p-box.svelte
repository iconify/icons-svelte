<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q51zeztgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q51zeztgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-p-box" {...props}></Icon>
