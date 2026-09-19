<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ws9_odf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c1ws9_odf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:calculator" {...props}></Icon>
