<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxk_x0b5m.css';
import '../../css/o/oa5lvwbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxk_x0b5m"/><path class="oa5lvwbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-wand-bold-duotone" {...props}></Icon>
