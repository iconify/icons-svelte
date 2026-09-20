<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxt7rxbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxt7rxbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-convertable" {...props}></Icon>
