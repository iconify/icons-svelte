<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j33nzxbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j33nzxbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-book-pages-bold" {...props}></Icon>
