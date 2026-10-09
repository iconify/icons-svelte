<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_1lwukaz.css';
import '../../css/g/gandzumwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p_1lwukaz"/><path class="gandzumwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:graduation-cap-20" {...props}></Icon>
