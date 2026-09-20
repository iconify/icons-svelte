<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s655yl9ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s655yl9ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:float-right" {...props}></Icon>
