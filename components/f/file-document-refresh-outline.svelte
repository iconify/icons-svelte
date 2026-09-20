<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iced0ob2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iced0ob2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-refresh-outline" {...props}></Icon>
