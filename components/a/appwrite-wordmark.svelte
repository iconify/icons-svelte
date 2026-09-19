<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvv2sxohs.css';
import '../../css/t/txt750bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xvv2sxohs"/><path class="txt750bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:appwrite-wordmark" {...props}></Icon>
