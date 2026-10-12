<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efr7zvbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efr7zvbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-left-filled" {...props}></Icon>
