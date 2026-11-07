<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p69thbcke.css';
import '../../css/r/r_skykbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p69thbcke"/><path class="r_skykbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chef-hat-bold-duotone" {...props}></Icon>
