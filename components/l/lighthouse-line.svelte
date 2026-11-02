<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdi7fsh1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdi7fsh1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lighthouse-line" {...props}></Icon>
