<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw8nvupj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw8nvupj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-pointing-left" {...props}></Icon>
