<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_nee0cyh.css';
import '../../css/k/kafmo0bpp.css';
import '../../css/l/lkpq_rbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j_nee0cyh"/><path class="kafmo0bpp"/><path class="lkpq_rbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:man-climbing" {...props}></Icon>
