<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig5xbqbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ig5xbqbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-rain-20" {...props}></Icon>
