<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc0qlpbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mc0qlpbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-fragment" {...props}></Icon>
