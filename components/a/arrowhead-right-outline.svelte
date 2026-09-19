<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu122ac1g.css';
import '../../css/s/s0ax18b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu122ac1g"/><path class="s0ax18b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrowhead-right-outline" {...props}></Icon>
