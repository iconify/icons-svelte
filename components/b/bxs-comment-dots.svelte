<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk9hjzb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9hjzb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-comment-dots" {...props}></Icon>
