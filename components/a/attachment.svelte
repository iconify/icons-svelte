<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn_bdhp3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn_bdhp3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:attachment" {...props}></Icon>
