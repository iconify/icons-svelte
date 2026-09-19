<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icagaq53q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icagaq53q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-rewind" {...props}></Icon>
