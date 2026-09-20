<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwngp28av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwngp28av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-error-outline" {...props}></Icon>
