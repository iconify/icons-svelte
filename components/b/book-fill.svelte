<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d11dj0w2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d11dj0w2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:book-fill" {...props}></Icon>
