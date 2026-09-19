<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfcs2q2pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hfcs2q2pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-square-heart-fill" {...props}></Icon>
