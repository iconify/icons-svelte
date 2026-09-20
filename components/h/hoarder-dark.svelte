<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiv-uob8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wiv-uob8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hoarder-dark" {...props}></Icon>
