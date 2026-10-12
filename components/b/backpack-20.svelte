<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6-fuybka.css';
import '../../css/t/tk8vkib5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6-fuybka"/><path class="tk8vkib5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:backpack-20" {...props}></Icon>
