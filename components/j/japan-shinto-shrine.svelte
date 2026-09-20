<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdeuny-bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cdeuny-bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-shinto-shrine" {...props}></Icon>
