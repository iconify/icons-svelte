<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd1hdgbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd1hdgbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-vertical-fill" {...props}></Icon>
