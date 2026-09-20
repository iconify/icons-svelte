<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lybmi-wnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lybmi-wnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:achievement-award" {...props}></Icon>
