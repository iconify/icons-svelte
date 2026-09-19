<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcpw23ryq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rcpw23ryq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hand-index-thumb" {...props}></Icon>
