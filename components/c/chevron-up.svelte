<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1gf8xb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1gf8xb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:chevron-up" {...props}></Icon>
