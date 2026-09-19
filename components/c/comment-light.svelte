<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr2-x1j7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2-x1j7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-light" {...props}></Icon>
