<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7x-ueboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7x-ueboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fish" {...props}></Icon>
