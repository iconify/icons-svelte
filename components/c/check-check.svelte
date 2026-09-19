<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4k2drbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4k2drbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:check-check" {...props}></Icon>
