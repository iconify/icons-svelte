<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ogkov_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_ogkov_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frequency-20" {...props}></Icon>
