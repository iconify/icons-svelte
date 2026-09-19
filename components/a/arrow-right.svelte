<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdoc90x5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdoc90x5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-right" {...props}></Icon>
