<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-1-nhi8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1-nhi8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-plus-fill-round" {...props}></Icon>
