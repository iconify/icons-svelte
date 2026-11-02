<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiu74tbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiu74tbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-line" {...props}></Icon>
