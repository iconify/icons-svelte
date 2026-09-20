<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce6t8tjjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6t8tjjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-arrow-right-outline" {...props}></Icon>
