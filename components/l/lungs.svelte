<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r78ox6b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r78ox6b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:lungs" {...props}></Icon>
