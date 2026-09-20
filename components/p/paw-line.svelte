<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frun5_jeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frun5_jeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paw-line" {...props}></Icon>
