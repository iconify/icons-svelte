<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5aw_t51u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5aw_t51u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-1-fill" {...props}></Icon>
