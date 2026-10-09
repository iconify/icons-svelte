<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzjyr_m9i.css';
import '../../css/e/ej_mrn1yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rzjyr_m9i"/><path class="ej_mrn1yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-20-bold" {...props}></Icon>
