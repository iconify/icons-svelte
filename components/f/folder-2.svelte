<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yod0hvbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yod0hvbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:folder-2" {...props}></Icon>
