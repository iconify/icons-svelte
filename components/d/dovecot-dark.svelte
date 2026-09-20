<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8x16zbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d8x16zbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dovecot-dark" {...props}></Icon>
