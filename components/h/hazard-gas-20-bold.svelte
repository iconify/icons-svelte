<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcia1ds6l.css';
import '../../css/f/fo9trqysu.css';
import '../../css/q/quuwtjdku.css';
import '../../css/f/fye7pfxns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="fo9trqysu"/><path class="quuwtjdku"/><path class="fye7pfxns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-gas-20-bold" {...props}></Icon>
