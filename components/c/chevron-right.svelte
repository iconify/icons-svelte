<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gay3w-bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gay3w-bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevron-right" {...props}></Icon>
