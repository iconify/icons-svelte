<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1qc2pr2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1qc2pr2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-standby" {...props}></Icon>
