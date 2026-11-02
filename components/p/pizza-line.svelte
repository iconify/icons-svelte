<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9x36qboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9x36qboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pizza-line" {...props}></Icon>
