<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4c_akmqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p4c_akmqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-with-arrow-bottom-right" {...props}></Icon>
