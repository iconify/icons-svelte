<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6og01bov.css';
import '../../css/r/riwyopb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6og01bov"/><path class="riwyopb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:negative-price-20" {...props}></Icon>
