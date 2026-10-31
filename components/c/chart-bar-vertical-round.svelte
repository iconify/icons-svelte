<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqrqvz3rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqrqvz3rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-vertical-round" {...props}></Icon>
