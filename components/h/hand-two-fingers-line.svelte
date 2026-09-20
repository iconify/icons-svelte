<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3w8pzz0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3w8pzz0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-two-fingers-line" {...props}></Icon>
