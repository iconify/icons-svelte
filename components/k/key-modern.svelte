<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn2aw68ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tn2aw68ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:key-modern" {...props}></Icon>
