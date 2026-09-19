<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2_f5cb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2_f5cb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:question-circle-fill" {...props}></Icon>
