<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybpzd0btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybpzd0btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firefox-line" {...props}></Icon>
