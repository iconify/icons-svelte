<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xown7vyye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xown7vyye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-right-sharp-duotone" {...props}></Icon>
