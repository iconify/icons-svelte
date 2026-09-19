<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmts5vxbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmts5vxbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookshelf-01" {...props}></Icon>
