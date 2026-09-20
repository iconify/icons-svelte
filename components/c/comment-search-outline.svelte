<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpraj3b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpraj3b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-search-outline" {...props}></Icon>
