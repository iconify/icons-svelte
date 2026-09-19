<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux8t0hbvv.css';
import '../../css/s/s9s7xp23i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ux8t0hbvv"/><path class="s9s7xp23i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calculator" {...props}></Icon>
