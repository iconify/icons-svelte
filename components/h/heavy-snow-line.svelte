<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs6yp6sra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6yp6sra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-snow-line" {...props}></Icon>
