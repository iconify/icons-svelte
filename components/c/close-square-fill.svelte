<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntkb4qi-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntkb4qi-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-square-fill" {...props}></Icon>
