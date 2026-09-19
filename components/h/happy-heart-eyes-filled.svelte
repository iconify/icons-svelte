<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvb7dyg7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvb7dyg7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:happy-heart-eyes-filled" {...props}></Icon>
