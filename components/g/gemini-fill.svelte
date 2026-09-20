<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly61nkbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly61nkbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gemini-fill" {...props}></Icon>
