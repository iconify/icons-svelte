<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9vvgn11d.css';
import '../../css/t/t52mucocr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9vvgn11d"/><path class="t52mucocr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-dashed-bold-duotone" {...props}></Icon>
