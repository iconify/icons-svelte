<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj7g8cc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zj7g8cc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:khronos" {...props}></Icon>
