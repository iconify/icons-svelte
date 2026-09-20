<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4_jpib6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l4_jpib6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hard-hat" {...props}></Icon>
