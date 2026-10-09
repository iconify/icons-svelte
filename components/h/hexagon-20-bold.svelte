<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsioiwbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsioiwbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hexagon-20-bold" {...props}></Icon>
