<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_01joir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nz_01joir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:divide-20-bold" {...props}></Icon>
