<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de61zybbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="de61zybbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:programok" {...props}></Icon>
