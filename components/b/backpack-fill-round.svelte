<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj2556zno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2556zno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:backpack-fill-round" {...props}></Icon>
