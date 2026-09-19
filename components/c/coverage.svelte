<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcefh-p8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dcefh-p8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:coverage" {...props}></Icon>
