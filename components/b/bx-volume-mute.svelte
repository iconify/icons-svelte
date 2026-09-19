<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2finz0wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2finz0wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-volume-mute" {...props}></Icon>
