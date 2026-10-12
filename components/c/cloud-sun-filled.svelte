<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2475zbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2475zbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-sun-filled" {...props}></Icon>
