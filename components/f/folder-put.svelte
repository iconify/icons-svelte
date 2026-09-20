<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1u40bb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e1u40bb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-put" {...props}></Icon>
