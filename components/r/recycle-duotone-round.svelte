<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyfh41bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfh41bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:recycle-duotone-round" {...props}></Icon>
