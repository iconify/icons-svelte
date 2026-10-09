<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn8593byb.css';
import '../../css/g/gdm6o-2_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wn8593byb"/><path class="gdm6o-2_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-air-balloon-20" {...props}></Icon>
