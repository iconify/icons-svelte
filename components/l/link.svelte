<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqu73ccux.css';
import '../../css/c/ccr-r5nke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqu73ccux"/><path class="ccr-r5nke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:link" {...props}></Icon>
