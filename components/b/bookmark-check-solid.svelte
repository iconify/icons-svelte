<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_8r6kb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_8r6kb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-check-solid" {...props}></Icon>
