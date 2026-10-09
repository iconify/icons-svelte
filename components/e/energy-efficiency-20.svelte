<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vng_kgbvl.css';
import '../../css/k/ke73g8b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vng_kgbvl"/><path class="ke73g8b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-efficiency-20" {...props}></Icon>
