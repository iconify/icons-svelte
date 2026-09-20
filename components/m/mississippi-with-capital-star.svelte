<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa_2w9b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qa_2w9b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mississippi-with-capital-star" {...props}></Icon>
