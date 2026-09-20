<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaol0eb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aaol0eb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:houzz" {...props}></Icon>
