<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv1b90jbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wv1b90jbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-on-ground-dragging-raft-to-water" {...props}></Icon>
