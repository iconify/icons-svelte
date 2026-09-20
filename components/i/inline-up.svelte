<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i90gq365a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i90gq365a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:inline-up" {...props}></Icon>
