<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoore9bru.css';
import '../../css/r/riiz-0est.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xoore9bru"/><path class="riiz-0est"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-sheets-dark" {...props}></Icon>
