<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhxlzbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emhxlzbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:repost" {...props}></Icon>
