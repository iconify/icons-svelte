<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8zc9pbaf.css';
import '../../css/o/odesuob1o.css';
import '../../css/w/w5u_c5a9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8zc9pbaf"/><path clip-rule="evenodd" class="odesuob1o"/><path class="w5u_c5a9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-smartphone-bold-duotone" {...props}></Icon>
