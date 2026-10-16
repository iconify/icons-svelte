<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei8_htdz.css';
import '../../css/w/wtq6wobvy.css';
import '../../css/g/g5a07ectm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="wtq6wobvy"/><path class="g5a07ectm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydrogen-20-bold" {...props}></Icon>
