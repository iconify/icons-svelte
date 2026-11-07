<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbi4wky7o.css';
import '../../css/s/sfo2tsbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbi4wky7o"/><path class="sfo2tsbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloudy-moon-bold-duotone" {...props}></Icon>
