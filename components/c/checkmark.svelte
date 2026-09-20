<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqmj-2b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqmj-2b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:checkmark" {...props}></Icon>
