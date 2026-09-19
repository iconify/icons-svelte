<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzlp1fnmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zzlp1fnmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:basket-arrow-down" {...props}></Icon>
