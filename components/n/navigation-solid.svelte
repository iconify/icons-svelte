<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trkb3cw4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trkb3cw4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-solid" {...props}></Icon>
