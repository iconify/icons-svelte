<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgk6z6b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bgk6z6b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:eye-closed" {...props}></Icon>
