<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk37tohnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kk37tohnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authgear" {...props}></Icon>
