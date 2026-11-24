<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q60-wi-ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q60-wi-ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-click-filled" {...props}></Icon>
