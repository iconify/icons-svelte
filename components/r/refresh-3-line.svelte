<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwfi32n6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwfi32n6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-3-line" {...props}></Icon>
