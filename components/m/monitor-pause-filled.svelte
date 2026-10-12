<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ty35bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2ty35bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-pause-filled" {...props}></Icon>
