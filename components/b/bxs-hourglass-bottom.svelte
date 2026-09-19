<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s79r90nvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s79r90nvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hourglass-bottom" {...props}></Icon>
