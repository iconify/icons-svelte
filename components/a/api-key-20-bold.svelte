<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvg-drbfm.css';
import '../../css/v/vx3fhbbqc.css';
import '../../css/k/kjepdxb8e.css';
import '../../css/j/jthdzbbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dvg-drbfm"/><path class="vx3fhbbqc"/><path class="kjepdxb8e"/><path class="jthdzbbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:api-key-20-bold" {...props}></Icon>
