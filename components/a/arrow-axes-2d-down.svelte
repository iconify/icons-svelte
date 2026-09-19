<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blah4vbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blah4vbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-axes-2d-down" {...props}></Icon>
