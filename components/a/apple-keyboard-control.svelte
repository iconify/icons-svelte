<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd3xg04we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3xg04we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-keyboard-control" {...props}></Icon>
