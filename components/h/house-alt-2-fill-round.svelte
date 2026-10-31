<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgipwwbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgipwwbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-2-fill-round" {...props}></Icon>
