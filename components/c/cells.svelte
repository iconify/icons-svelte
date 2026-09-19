<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re8d6dfzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re8d6dfzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cells" {...props}></Icon>
