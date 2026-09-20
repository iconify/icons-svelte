<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_m0xwdts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_m0xwdts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:betula-bottom-right-horizontal-line" {...props}></Icon>
