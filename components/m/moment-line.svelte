<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbm6ne5it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbm6ne5it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moment-line" {...props}></Icon>
