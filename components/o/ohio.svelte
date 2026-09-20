<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1fm_tbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z1fm_tbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ohio" {...props}></Icon>
