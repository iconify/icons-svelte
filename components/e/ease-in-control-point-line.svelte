<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fndko-17y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fndko-17y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-control-point-line" {...props}></Icon>
