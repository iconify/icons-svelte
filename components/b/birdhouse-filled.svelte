<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii4mixb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii4mixb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:birdhouse-filled" {...props}></Icon>
