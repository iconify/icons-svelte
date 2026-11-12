<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zew7-c2gj.css';
import '../../css/v/vea0ry4ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zew7-c2gj"/><path class="vea0ry4ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextbeats" {...props}></Icon>
