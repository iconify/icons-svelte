<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9j9rvb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e9j9rvb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:plug" {...props}></Icon>
