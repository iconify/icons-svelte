<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psh4icc1n.css';
import '../../css/u/uo6pjzbsg.css';
import '../../css/o/ozo3l73pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="psh4icc1n"/><path class="uo6pjzbsg"/><path class="ozo3l73pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:auto-scroll" {...props}></Icon>
