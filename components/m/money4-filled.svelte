<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdfne-b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdfne-b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money4-filled" {...props}></Icon>
