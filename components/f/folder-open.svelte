<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fykzdacxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fykzdacxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-open" {...props}></Icon>
