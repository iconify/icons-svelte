<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_5i6l4fk.css';
import '../../css/l/lrz954bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g_5i6l4fk"/><path class="lrz954bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-tree" {...props}></Icon>
