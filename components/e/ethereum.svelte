<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc3jlxb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3jlxb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ethereum" {...props}></Icon>
