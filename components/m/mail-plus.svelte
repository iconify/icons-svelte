<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1e30abbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s1e30abbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:mail-plus" {...props}></Icon>
