<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lidnvnbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lidnvnbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:guitar-line" {...props}></Icon>
