<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni6nc-c3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni6nc-c3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ruler-2-fill" {...props}></Icon>
