<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt8f-3eoh.css';
import '../../css/s/s9tollx4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="s9tollx4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-heart-20-bold" {...props}></Icon>
