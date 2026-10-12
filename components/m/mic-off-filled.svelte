<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff9vdub5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff9vdub5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mic-off-filled" {...props}></Icon>
