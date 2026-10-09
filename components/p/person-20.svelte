<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7yn3-0ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7yn3-0ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:person-20" {...props}></Icon>
