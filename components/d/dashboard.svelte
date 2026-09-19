<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncx4c8byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncx4c8byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dashboard" {...props}></Icon>
