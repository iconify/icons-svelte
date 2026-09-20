<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvfqrdebp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nvfqrdebp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-with-battlements-and-turret" {...props}></Icon>
