<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr2a8d89r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2a8d89r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-older-woman-gloss" {...props}></Icon>
