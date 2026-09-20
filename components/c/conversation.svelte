<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz1nfzvvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gz1nfzvvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:conversation" {...props}></Icon>
