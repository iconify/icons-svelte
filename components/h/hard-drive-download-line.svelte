<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3bmh4yvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3bmh4yvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hard-drive-download-line" {...props}></Icon>
