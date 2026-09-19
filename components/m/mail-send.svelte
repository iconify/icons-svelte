<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8wh6ihst.css';
import '../../css/c/cd1qz4bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8wh6ihst"/><path class="cd1qz4bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:mail-send" {...props}></Icon>
