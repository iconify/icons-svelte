<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1u15frkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1u15frkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-03" {...props}></Icon>
