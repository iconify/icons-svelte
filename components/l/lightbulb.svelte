<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1kfb4bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1kfb4bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:lightbulb" {...props}></Icon>
