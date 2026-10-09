<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u56_ywbll.css';
import '../../css/a/ahi5vcc6u.css';
import '../../css/f/fxlzn8gcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u56_ywbll"/><path class="ahi5vcc6u"/><path class="fxlzn8gcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dumbbell-20-bold" {...props}></Icon>
