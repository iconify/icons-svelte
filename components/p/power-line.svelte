<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-8b8vb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-8b8vb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:power-line" {...props}></Icon>
