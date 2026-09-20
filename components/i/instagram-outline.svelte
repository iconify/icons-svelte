<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlp_1cbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qlp_1cbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:instagram-outline" {...props}></Icon>
