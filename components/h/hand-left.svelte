<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8aqobc0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8aqobc0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-left" {...props}></Icon>
