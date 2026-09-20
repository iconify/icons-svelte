<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3wtdab_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i3wtdab_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-down-left-stipple-inner" {...props}></Icon>
