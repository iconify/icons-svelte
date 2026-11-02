<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vziw5eblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vziw5eblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:audio-tape-fill" {...props}></Icon>
