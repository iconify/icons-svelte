<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr40wtbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":208,"height":456};
const content = `<path class="tr40wtbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:right" {...props}></Icon>
