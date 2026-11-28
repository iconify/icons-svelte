<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4rph6uhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4rph6uhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:curtains-solid" {...props}></Icon>
