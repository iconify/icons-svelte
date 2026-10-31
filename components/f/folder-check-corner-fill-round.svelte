<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddw29zbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddw29zbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-check-corner-fill-round" {...props}></Icon>
