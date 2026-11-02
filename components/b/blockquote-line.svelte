<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6fn8xqie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6fn8xqie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:blockquote-line" {...props}></Icon>
