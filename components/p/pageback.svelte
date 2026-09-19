<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnv4d03jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xnv4d03jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pageback" {...props}></Icon>
