<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2zzj1mmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2zzj1mmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crown-20" {...props}></Icon>
