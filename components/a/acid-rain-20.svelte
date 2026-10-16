<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhj96-tym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uhj96-tym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acid-rain-20" {...props}></Icon>
