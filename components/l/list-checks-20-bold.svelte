<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjw_5r1kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vjw_5r1kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-checks-20-bold" {...props}></Icon>
