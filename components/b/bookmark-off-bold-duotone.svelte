<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfg33ubfc.css';
import '../../css/p/pjltp9b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfg33ubfc"/><path class="pjltp9b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-off-bold-duotone" {...props}></Icon>
