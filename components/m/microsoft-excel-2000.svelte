<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sibkcjb8c.css';
import '../../css/t/ts2m0_f8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sibkcjb8c"/><path class="ts2m0_f8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2000" {...props}></Icon>
