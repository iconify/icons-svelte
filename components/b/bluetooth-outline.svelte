<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b___szmht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b___szmht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bluetooth-outline" {...props}></Icon>
