<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy9ieug-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yy9ieug-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cc-discover" {...props}></Icon>
