<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe3d6k5kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oe3d6k5kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-moon-20" {...props}></Icon>
