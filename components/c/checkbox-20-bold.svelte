<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfgcicctr.css';
import '../../css/l/lfowfacnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="lfowfacnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:checkbox-20-bold" {...props}></Icon>
