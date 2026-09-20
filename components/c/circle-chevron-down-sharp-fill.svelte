<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey3bs5pmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3bs5pmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-down-sharp-fill" {...props}></Icon>
