<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r--_kryyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r--_kryyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flower-outline" {...props}></Icon>
