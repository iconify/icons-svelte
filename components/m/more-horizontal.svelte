<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru29i1boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru29i1boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:more-horizontal" {...props}></Icon>
