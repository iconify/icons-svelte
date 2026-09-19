<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmejw90ec.css';
import '../../css/b/b8av53bdl.css';
import '../../css/b/bncxwo81m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmejw90ec"/><path class="b8av53bdl"/><path class="bncxwo81m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-albums" {...props}></Icon>
