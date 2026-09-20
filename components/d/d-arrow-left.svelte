<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt6tuxrbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zt6tuxrbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:d-arrow-left" {...props}></Icon>
