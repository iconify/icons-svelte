<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmkgw6vvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmkgw6vvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-sparkle-corner-round" {...props}></Icon>
