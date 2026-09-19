<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kot-p6b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kot-p6b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:chat-2" {...props}></Icon>
