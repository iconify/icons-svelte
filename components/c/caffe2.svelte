<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri13whboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ri13whboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:caffe2" {...props}></Icon>
