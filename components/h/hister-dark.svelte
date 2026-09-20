<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d874l2bcu.css';
import '../../css/n/ngc99bfxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d874l2bcu"/><path class="ngc99bfxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hister-dark" {...props}></Icon>
