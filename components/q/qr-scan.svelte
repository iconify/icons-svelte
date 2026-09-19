<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvaaipbio.css';
import '../../css/v/v6qkiubvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvaaipbio"/><path class="v6qkiubvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:qr-scan" {...props}></Icon>
