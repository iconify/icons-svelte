<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrb7icb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lrb7icb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-doc-filled" {...props}></Icon>
