<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crgjunekl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="crgjunekl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:inkscape" {...props}></Icon>
