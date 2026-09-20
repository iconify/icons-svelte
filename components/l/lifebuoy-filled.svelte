<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry--jlbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry--jlbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lifebuoy-filled" {...props}></Icon>
