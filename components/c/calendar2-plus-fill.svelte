<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bstkd1bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bstkd1bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-plus-fill" {...props}></Icon>
