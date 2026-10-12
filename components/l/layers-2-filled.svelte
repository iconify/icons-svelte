<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqp3zebpd.css';
import '../../css/l/l_9-3eagj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqp3zebpd"/><path class="l_9-3eagj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-2-filled" {...props}></Icon>
