<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7uoogagy.css';
import '../../css/p/pwof45wsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7uoogagy"/><path class="pwof45wsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-angle-bold-duotone" {...props}></Icon>
