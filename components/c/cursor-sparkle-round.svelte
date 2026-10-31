<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziz0u5bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziz0u5bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-sparkle-round" {...props}></Icon>
