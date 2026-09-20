<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf6fy74a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ocf6fy74a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:printer" {...props}></Icon>
