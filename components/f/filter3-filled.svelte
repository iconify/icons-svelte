<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rok7fibkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rok7fibkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:filter3-filled" {...props}></Icon>
