<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixyvvha0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixyvvha0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-dollar-filled" {...props}></Icon>
