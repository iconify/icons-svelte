<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_np0pzjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_np0pzjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluffychat-light" {...props}></Icon>
