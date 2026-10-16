<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4__ecb7c.css';
import '../../css/h/hc_-pfegj.css';
import '../../css/x/xaulnjbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d4__ecb7c"/><path class="hc_-pfegj"/><path class="xaulnjbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-alert-48" {...props}></Icon>
