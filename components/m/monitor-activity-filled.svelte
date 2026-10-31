<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq_bupb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dq_bupb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-activity-filled" {...props}></Icon>
