<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxt-x2bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxt-x2bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-comment-check" {...props}></Icon>
