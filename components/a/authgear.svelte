<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2_j2sbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2_j2sbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authgear" {...props}></Icon>
