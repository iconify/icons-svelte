<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd95kpb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pd95kpb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:column-spacing" {...props}></Icon>
