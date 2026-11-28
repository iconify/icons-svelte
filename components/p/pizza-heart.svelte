<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoj50dbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoj50dbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pizza-heart" {...props}></Icon>
