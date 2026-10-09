<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqiswsboe.css';
import '../../css/r/rynce1opb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kqiswsboe"/><path class="rynce1opb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:music-48-bold" {...props}></Icon>
