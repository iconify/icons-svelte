<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv42s-bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv42s-bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attachment-duotone" {...props}></Icon>
