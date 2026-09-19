<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q78n-474u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="q78n-474u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bullet-list-2" {...props}></Icon>
