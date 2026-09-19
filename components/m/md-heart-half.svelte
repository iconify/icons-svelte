<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfxfn_o5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nfxfn_o5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-heart-half" {...props}></Icon>
