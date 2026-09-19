<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu2bs-teb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zu2bs-teb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mask-ventilator" {...props}></Icon>
