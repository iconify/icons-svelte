<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr2fh6b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cr2fh6b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-8" {...props}></Icon>
