<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvs-pbb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvs-pbb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cpu-alert" {...props}></Icon>
