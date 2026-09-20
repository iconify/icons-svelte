<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn4d89lsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn4d89lsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bandcamp-light" {...props}></Icon>
