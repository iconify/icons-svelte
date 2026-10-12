<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfbsv3wdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfbsv3wdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fishing-rod-filled" {...props}></Icon>
