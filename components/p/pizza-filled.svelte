<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_xcrkbeg.css';
import '../../css/o/ojv9pubkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_xcrkbeg"/><path class="ojv9pubkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pizza-filled" {...props}></Icon>
