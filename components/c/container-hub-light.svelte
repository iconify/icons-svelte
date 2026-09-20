<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejgmd2bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejgmd2bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:container-hub-light" {...props}></Icon>
