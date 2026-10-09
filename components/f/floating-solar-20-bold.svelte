<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5zz3vvln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v5zz3vvln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floating-solar-20-bold" {...props}></Icon>
