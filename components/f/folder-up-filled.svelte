<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncglfsxcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncglfsxcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-up-filled" {...props}></Icon>
