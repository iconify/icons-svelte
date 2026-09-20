<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac8ulaccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac8ulaccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chart-column-decreasing-sharp" {...props}></Icon>
