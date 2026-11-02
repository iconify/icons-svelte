<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-v7ou0hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-v7ou0hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-heart-line" {...props}></Icon>
