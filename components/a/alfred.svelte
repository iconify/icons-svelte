<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjvg18z4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjvg18z4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alfred" {...props}></Icon>
