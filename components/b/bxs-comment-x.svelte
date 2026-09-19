<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_eucm9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_eucm9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-comment-x" {...props}></Icon>
