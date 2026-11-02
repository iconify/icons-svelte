<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whx59cbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whx59cbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brief-line" {...props}></Icon>
