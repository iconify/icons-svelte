<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv4_ow18w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv4_ow18w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-3-fill" {...props}></Icon>
