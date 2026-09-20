<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ixqfx6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2ixqfx6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:right-square" {...props}></Icon>
