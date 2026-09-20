<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haowqoako.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haowqoako"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-line" {...props}></Icon>
