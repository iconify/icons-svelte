<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m640zw-kt.css';
import '../../css/s/s4s4c3b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m640zw-kt"/><path class="s4s4c3b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ballotboxwithboldscriptx" {...props}></Icon>
