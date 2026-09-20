<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evgiiqbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evgiiqbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-refresh" {...props}></Icon>
