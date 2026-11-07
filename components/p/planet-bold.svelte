<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfi_pwizc.css';
import '../../css/t/tc8lqywfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfi_pwizc"/><path class="tc8lqywfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-bold" {...props}></Icon>
