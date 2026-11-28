<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igjbv8bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igjbv8bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevron-circle-right" {...props}></Icon>
