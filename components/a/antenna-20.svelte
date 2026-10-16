<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h210bm66l.css';
import '../../css/k/k7ytu5blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h210bm66l"/><path class="k7ytu5blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:antenna-20" {...props}></Icon>
