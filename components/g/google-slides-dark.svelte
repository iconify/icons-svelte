<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoore9bru.css';
import '../../css/a/ailbzjhcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xoore9bru"/><path class="ailbzjhcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-slides-dark" {...props}></Icon>
