<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl79juz7d.css';
import '../../css/i/i3l80h-5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl79juz7d"/><path class="i3l80h-5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-check-bold-duotone" {...props}></Icon>
