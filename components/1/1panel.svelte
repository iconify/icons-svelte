<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdbkcyrsw.css';
import '../../css/c/c7_pmq9wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdbkcyrsw"/><path class="c7_pmq9wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:1panel" {...props}></Icon>
