<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3u-ax48z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3u-ax48z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connected-circle-filled" {...props}></Icon>
