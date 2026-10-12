<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzowugs6h.css';
import '../../css/y/yz3e6tb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzowugs6h"/><path class="yz3e6tb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cable-car-filled" {...props}></Icon>
