<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2n8w6boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2n8w6boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-2-line" {...props}></Icon>
