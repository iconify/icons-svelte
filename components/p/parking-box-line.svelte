<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abysg8brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abysg8brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:parking-box-line" {...props}></Icon>
