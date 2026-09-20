<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbubq_bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbubq_bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:folder-list" {...props}></Icon>
