<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxr7eibdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bxr7eibdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-all-duo" {...props}></Icon>
