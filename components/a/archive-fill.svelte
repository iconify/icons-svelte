<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y697366mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y697366mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:archive-fill" {...props}></Icon>
