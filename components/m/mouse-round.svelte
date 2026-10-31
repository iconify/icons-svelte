<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv1nz2brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv1nz2brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mouse-round" {...props}></Icon>
