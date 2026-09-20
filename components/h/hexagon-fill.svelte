<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-0r88qhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-0r88qhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hexagon-fill" {...props}></Icon>
