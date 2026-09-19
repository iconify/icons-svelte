<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4250zhsi.css';
import '../../css/l/l8da1zbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f4250zhsi"/><path class="l8da1zbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-linkedin" {...props}></Icon>
