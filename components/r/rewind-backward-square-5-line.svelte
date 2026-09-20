<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbk7jibmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbk7jibmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-5-line" {...props}></Icon>
