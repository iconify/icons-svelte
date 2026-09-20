<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-3wim6xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-3wim6xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-link-outline" {...props}></Icon>
