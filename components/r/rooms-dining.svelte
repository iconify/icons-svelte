<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl4d36m1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl4d36m1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-dining" {...props}></Icon>
