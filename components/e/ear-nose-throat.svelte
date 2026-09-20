<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxvedcdm.css';
import '../../css/a/alb_3ybms.css';
import '../../css/e/eu7poe5sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="haxvedcdm"/><path class="alb_3ybms"/><path class="eu7poe5sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:ear-nose-throat" {...props}></Icon>
