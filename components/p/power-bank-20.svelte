<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxhnq1bnf.css';
import '../../css/r/rx2al_b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxhnq1bnf"/><path class="rx2al_b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-bank-20" {...props}></Icon>
