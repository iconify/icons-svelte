<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcz7dqaye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz7dqaye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-down-box" {...props}></Icon>
