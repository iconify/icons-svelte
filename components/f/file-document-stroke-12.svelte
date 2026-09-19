<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suhh-xi_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="suhh-xi_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-document-stroke-12" {...props}></Icon>
