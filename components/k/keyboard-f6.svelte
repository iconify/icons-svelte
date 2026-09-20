<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6o4olbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6o4olbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-f6" {...props}></Icon>
