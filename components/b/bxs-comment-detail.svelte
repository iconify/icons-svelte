<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiqhgmb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiqhgmb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-comment-detail" {...props}></Icon>
