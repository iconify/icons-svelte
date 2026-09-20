<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de9rmfxkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de9rmfxkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:printables" {...props}></Icon>
