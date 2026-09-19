<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi5f0rxnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fi5f0rxnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:notesdate" {...props}></Icon>
