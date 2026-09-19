<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt88iibqu.css';
import '../../css/n/nsbcuotwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt88iibqu"/><path class="nsbcuotwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:calculator" {...props}></Icon>
