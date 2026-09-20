<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enspv9bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enspv9bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-send" {...props}></Icon>
