<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op9p-6diq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op9p-6diq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dutch-windmill-line" {...props}></Icon>
