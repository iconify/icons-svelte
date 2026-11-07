<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq9kkcbbd.css';
import '../../css/d/d56vnzbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq9kkcbbd"/><path class="d56vnzbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-bold-duotone" {...props}></Icon>
