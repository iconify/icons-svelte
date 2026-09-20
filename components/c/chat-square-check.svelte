<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xofr0ybof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xofr0ybof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-check" {...props}></Icon>
