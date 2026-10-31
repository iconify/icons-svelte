<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdckqzbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdckqzbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:remove-formatting-duotone-round" {...props}></Icon>
