<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnr-pth_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnr-pth_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hanger-2-filled" {...props}></Icon>
