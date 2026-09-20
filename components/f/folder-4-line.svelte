<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm3u1cb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm3u1cb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-4-line" {...props}></Icon>
