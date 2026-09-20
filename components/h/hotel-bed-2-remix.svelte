<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfxjyu9fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfxjyu9fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-bed-2-remix" {...props}></Icon>
