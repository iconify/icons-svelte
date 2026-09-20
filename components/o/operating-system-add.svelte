<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_05bafr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pk_05bafr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:operating-system-add" {...props}></Icon>
