<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geb7k3hdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="geb7k3hdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-rating-20" {...props}></Icon>
