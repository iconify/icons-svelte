<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvqcq-bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kvqcq-bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:quora" {...props}></Icon>
