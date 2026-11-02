<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylkfh-8lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylkfh-8lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:handshake-line" {...props}></Icon>
