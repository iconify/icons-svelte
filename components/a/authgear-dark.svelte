<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki-0lmrvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ki-0lmrvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authgear-dark" {...props}></Icon>
