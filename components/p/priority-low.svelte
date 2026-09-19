<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1-w6z7eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1-w6z7eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:priority-low" {...props}></Icon>
