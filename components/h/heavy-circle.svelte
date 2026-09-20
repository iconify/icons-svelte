<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5u1_b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xg5u1_b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heavy-circle" {...props}></Icon>
