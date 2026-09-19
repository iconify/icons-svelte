<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfy3q2bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfy3q2bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-pointer-ban" {...props}></Icon>
