<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl7y-9koh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dl7y-9koh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-layer-2-solid" {...props}></Icon>
