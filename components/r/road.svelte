<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re6-2bchy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re6-2bchy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:road" {...props}></Icon>
