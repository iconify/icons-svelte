<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwog5qh3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwog5qh3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbassets-dark" {...props}></Icon>
