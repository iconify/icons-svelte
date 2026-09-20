<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb65a0hev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hb65a0hev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-ok" {...props}></Icon>
