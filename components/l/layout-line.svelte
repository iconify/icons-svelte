<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiytj0umg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiytj0umg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-line" {...props}></Icon>
