<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb1r76bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nb1r76bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:c3" {...props}></Icon>
