<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvuoxcc7c.css';
import '../../css/b/bbi4wky7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvuoxcc7c"/><path class="bbi4wky7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-sleep-bold-duotone" {...props}></Icon>
