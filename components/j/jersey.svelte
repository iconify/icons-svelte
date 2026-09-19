<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg0-icc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pg0-icc4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:jersey" {...props}></Icon>
