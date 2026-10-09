<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjw5bmbkb.css';
import '../../css/g/gy2b850nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vjw5bmbkb"/><path class="gy2b850nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-20" {...props}></Icon>
