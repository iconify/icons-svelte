<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3tjkyblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e3tjkyblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish1-sad" {...props}></Icon>
