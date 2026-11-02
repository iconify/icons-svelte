<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4a1zheef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4a1zheef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bread-line" {...props}></Icon>
