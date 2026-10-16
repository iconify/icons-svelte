<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma-ovdbct.css';
import '../../css/o/o95_lvbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ma-ovdbct"/><path class="o95_lvbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clamp-meter-20-bold" {...props}></Icon>
