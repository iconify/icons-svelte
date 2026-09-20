<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip9fitivl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip9fitivl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:file-download-line" {...props}></Icon>
