<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o01tzxiux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o01tzxiux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:enter-door-line" {...props}></Icon>
