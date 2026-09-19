<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-nc6b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zb-nc6b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:clone-to-desktop" {...props}></Icon>
