<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzej9cc4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="pzej9cc4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-locked" {...props}></Icon>
