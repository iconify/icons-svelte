<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3gb8_t8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3gb8_t8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2018-light" {...props}></Icon>
