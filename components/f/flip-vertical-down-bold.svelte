<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdshv-w4n.css';
import '../../css/j/j-cb_fbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdshv-w4n"/><path class="j-cb_fbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flip-vertical-down-bold" {...props}></Icon>
