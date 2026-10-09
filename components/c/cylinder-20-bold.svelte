<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvmjd2aub.css';
import '../../css/f/f6d284boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pvmjd2aub"/><path class="f6d284boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cylinder-20-bold" {...props}></Icon>
