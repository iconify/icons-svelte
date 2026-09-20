<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqn-pgrxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn-pgrxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-up-left-fill" {...props}></Icon>
