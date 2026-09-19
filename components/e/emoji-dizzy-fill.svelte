<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn4-air-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zn4-air-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-dizzy-fill" {...props}></Icon>
