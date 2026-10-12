<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttn1zkbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttn1zkbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:navigation-off-filled" {...props}></Icon>
