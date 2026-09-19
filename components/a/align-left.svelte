<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh70bkjmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh70bkjmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:align-left" {...props}></Icon>
