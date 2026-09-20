<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw2vlobaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cw2vlobaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-yen-yuan" {...props}></Icon>
