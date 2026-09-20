<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl7hgnbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl7hgnbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-multiple-plus" {...props}></Icon>
