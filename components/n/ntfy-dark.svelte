<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph-134bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ph-134bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ntfy-dark" {...props}></Icon>
