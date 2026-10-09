<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivpnqg4j.css';
import '../../css/l/layzn__cg.css';
import '../../css/k/keyr8hhna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="layzn__cg"/><path class="keyr8hhna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-3x3-20-bold" {...props}></Icon>
