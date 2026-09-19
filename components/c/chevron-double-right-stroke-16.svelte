<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoqo4lbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qoqo4lbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-right-stroke-16" {...props}></Icon>
