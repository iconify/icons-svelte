<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq0k25o0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kq0k25o0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:mail" {...props}></Icon>
