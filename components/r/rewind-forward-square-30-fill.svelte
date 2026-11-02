<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxfrqy5fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxfrqy5fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-30-fill" {...props}></Icon>
