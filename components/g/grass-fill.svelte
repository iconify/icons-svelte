<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqqj8-tng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqqj8-tng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grass-fill" {...props}></Icon>
