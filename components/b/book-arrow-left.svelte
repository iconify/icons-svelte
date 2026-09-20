<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwjnzqejb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwjnzqejb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-left" {...props}></Icon>
