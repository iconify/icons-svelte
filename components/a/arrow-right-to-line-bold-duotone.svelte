<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi3uxcbzc.css';
import '../../css/d/duqz644oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi3uxcbzc"/><path class="duqz644oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-to-line-bold-duotone" {...props}></Icon>
