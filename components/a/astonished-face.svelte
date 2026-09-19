<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzc2ysb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lzc2ysb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:astonished-face" {...props}></Icon>
