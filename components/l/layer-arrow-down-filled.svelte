<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl153uk6t.css';
import '../../css/r/rv21otbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl153uk6t"/><path class="rv21otbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layer-arrow-down-filled" {...props}></Icon>
