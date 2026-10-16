<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khylky-1c.css';
import '../../css/t/t-6ze0bzb.css';
import '../../css/n/non-6ivtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="khylky-1c"/><path class="t-6ze0bzb"/><path class="non-6ivtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-alarm-20" {...props}></Icon>
