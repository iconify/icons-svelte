<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4eov22z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4eov22z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:file-word" {...props}></Icon>
