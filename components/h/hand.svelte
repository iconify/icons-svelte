<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltms_d40t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltms_d40t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand" {...props}></Icon>
