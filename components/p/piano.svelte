<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up_ob0yqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="up_ob0yqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:piano" {...props}></Icon>
