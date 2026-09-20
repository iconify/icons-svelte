<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxvdnobkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxvdnobkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-10-circle-outline" {...props}></Icon>
