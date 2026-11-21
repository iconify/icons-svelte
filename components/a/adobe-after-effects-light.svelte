<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r10ma0e2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r10ma0e2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-after-effects-light" {...props}></Icon>
