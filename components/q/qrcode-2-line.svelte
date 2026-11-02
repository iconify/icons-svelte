<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae6vf0y8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae6vf0y8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:qrcode-2-line" {...props}></Icon>
