<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsomaxd5w.css';
import '../../css/s/sc_o8zb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsomaxd5w"/><path class="sc_o8zb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-check" {...props}></Icon>
