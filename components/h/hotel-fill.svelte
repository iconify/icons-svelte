<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4pa2sbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4pa2sbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotel-fill" {...props}></Icon>
