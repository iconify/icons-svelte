<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmn6vv7gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmn6vv7gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mention-24" {...props}></Icon>
