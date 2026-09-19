<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz9gb9bqr.css';
import '../../css/r/rndnw4b9p.css';
import '../../css/x/xray__lap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="uz9gb9bqr"/><path class="rndnw4b9p"/><path class="xray__lap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:baggage-claim" {...props}></Icon>
