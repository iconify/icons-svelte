<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chdz1wbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chdz1wbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-bookmark-outline" {...props}></Icon>
