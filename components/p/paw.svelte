<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avml2tojl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1536};
const content = `<path class="avml2tojl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:paw" {...props}></Icon>
