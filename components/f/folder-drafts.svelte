<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9-3pccvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g9-3pccvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-drafts" {...props}></Icon>
