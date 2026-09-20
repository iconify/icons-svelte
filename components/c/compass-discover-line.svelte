<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmcm3dd5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmcm3dd5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-discover-line" {...props}></Icon>
