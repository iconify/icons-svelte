<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjh0zxifh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjh0zxifh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:app-window-gear" {...props}></Icon>
