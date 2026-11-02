<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wci0isvfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wci0isvfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dot-grid-line" {...props}></Icon>
