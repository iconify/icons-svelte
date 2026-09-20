<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf03ylb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf03ylb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-2-fill" {...props}></Icon>
