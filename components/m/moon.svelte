<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axnqpdh7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axnqpdh7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:moon" {...props}></Icon>
