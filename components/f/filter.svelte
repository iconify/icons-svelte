<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b74u6lyni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b74u6lyni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:filter" {...props}></Icon>
