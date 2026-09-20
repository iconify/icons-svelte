<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu8cdcbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu8cdcbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:party-popper" {...props}></Icon>
