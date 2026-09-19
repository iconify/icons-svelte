<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5j6f3bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5j6f3bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish4-very-sad" {...props}></Icon>
