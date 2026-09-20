<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht0_sf_dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht0_sf_dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mclaren" {...props}></Icon>
