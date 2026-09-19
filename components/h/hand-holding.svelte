<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8doegbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="r8doegbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding" {...props}></Icon>
