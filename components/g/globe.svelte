<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds-hzohyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds-hzohyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:globe" {...props}></Icon>
