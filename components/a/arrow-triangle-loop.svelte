<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlha15byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlha15byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-triangle-loop" {...props}></Icon>
