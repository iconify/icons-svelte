<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6b4f9b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6b4f9b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hot-tub-water-filled" {...props}></Icon>
