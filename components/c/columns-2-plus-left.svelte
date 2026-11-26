<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz97d6w4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz97d6w4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:columns-2-plus-left" {...props}></Icon>
