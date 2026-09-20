<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0i4fccqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x0i4fccqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:chevron-right" {...props}></Icon>
