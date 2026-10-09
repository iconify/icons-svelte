<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soxs6zviv.css';
import '../../css/v/vjp44lm8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="soxs6zviv"/><path class="vjp44lm8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammer-20-bold" {...props}></Icon>
