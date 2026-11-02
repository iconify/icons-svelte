<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td06nob6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td06nob6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firework-line" {...props}></Icon>
