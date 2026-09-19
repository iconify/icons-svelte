<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suh-k03fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="suh-k03fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-document-fill-12" {...props}></Icon>
