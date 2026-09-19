<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1pkisb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="u1pkisb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignbottomedge" {...props}></Icon>
