<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijd7q6vwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijd7q6vwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile" {...props}></Icon>
