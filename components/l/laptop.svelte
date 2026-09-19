<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-vgquoff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1280};
const content = `<path class="p-vgquoff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:laptop" {...props}></Icon>
