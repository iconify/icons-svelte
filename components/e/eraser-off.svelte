<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlkhq1c-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkhq1c-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eraser-off" {...props}></Icon>
