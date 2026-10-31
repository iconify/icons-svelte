<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5v90e9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5v90e9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-click-round" {...props}></Icon>
