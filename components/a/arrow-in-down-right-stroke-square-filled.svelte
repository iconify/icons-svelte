<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvbix7bxx.css';
import '../../css/s/sldl10bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvbix7bxx"/><path class="sldl10bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-right-stroke-square-filled" {...props}></Icon>
