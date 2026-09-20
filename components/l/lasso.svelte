<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpz0oeb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpz0oeb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:lasso" {...props}></Icon>
