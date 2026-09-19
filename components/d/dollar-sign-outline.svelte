<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojpr01bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ojpr01bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dollar-sign-outline" {...props}></Icon>
