<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuk17vbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuk17vbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-box-plus" {...props}></Icon>
