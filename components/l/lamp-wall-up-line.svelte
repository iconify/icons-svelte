<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z38osacau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z38osacau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lamp-wall-up-line" {...props}></Icon>
