<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlolbtbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":403,"height":512};
const content = `<path class="hlolbtbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:razzle" {...props}></Icon>
