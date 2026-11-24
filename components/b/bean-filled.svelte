<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4d3_byfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n4d3_byfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bean-filled" {...props}></Icon>
