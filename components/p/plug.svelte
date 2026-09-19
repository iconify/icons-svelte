<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbw451crf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mbw451crf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plug" {...props}></Icon>
