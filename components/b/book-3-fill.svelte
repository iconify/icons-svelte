<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7iy0jbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7iy0jbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-3-fill" {...props}></Icon>
