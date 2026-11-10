<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-5-jrbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d-5-jrbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:lighthouse" {...props}></Icon>
