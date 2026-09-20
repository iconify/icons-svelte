<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiv-hu0xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oiv-hu0xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:euro" {...props}></Icon>
