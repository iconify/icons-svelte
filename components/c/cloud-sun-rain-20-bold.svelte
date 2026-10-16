<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ly-n7ye.css';
import '../../css/d/dzz1crbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n9ly-n7ye"/><path class="dzz1crbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-rain-20-bold" {...props}></Icon>
