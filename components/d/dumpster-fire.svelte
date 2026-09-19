<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukdg_s_uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ukdg_s_uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dumpster-fire" {...props}></Icon>
