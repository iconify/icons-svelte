<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1b95sj3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1b95sj3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:parachute-box" {...props}></Icon>
