<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuru8lc6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuru8lc6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:magnet-filled" {...props}></Icon>
