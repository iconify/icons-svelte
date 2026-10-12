<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuff21y9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuff21y9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:door-stairwell-filled" {...props}></Icon>
