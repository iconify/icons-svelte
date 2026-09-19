<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrcy25pqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrcy25pqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-close" {...props}></Icon>
