<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68s7nb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="m68s7nb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:monument" {...props}></Icon>
