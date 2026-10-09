<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s--xkeuto.css';
import '../../css/j/j4u5ysbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s--xkeuto"/><path class="j4u5ysbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-location-20-bold" {...props}></Icon>
