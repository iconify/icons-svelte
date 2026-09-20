<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugn75zu8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ugn75zu8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-download" {...props}></Icon>
