<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfcgk_l-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zfcgk_l-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:nut-and-bolt" {...props}></Icon>
