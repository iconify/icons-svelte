<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_vsq7l3i.css';
import '../../css/w/w5fdibb6b.css';
import '../../css/p/ps5c3qbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="w5fdibb6b"/><path class="ps5c3qbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-minus-filled" {...props}></Icon>
