<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp5pjiolx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="xp5pjiolx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:heartbeat" {...props}></Icon>
