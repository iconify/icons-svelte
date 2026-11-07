<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxqrd9b8t.css';
import '../../css/i/i3l80h-5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxqrd9b8t"/><path class="i3l80h-5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-bold-duotone" {...props}></Icon>
