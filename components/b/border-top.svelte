<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvxsaw3yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvxsaw3yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-top" {...props}></Icon>
