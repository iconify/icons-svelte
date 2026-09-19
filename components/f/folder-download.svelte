<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am802ybiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am802ybiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:folder-download" {...props}></Icon>
