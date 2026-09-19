<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkygmcb8t.css';
import '../../css/a/ah052tbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkygmcb8t"/><path class="ah052tbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-star-alt-filled" {...props}></Icon>
