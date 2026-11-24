<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvdvp0-cq.css';
import '../../css/r/rii3008cf.css';
import '../../css/y/yxwk1vbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvdvp0-cq"/><path class="rii3008cf"/><path class="yxwk1vbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-drizzle-filled" {...props}></Icon>
