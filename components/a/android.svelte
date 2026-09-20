<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nth2z_w3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nth2z_w3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android" {...props}></Icon>
