<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr9p9rb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr9p9rb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:book-open-line" {...props}></Icon>
