<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3nlvcvue.css';
import '../../css/l/llokiq9ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3nlvcvue"/><path class="llokiq9ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-search-filled" {...props}></Icon>
