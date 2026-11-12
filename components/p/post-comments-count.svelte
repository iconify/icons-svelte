<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo76gwbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo76gwbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:post-comments-count" {...props}></Icon>
