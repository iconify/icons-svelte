<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hepctmbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hepctmbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:locate-off-line" {...props}></Icon>
