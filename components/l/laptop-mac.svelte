<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9qqa1tma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="w9qqa1tma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:laptop-mac" {...props}></Icon>
