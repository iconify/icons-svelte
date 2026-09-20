<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8ufprbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ufprbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:frame-line" {...props}></Icon>
