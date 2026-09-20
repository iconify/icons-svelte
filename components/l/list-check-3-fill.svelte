<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1d-uv5we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1d-uv5we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-3-fill" {...props}></Icon>
