<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_p0p0b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_p0p0b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-bar-stacked-24px" {...props}></Icon>
