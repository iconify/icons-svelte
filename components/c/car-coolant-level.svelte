<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu-lndb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-lndb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-coolant-level" {...props}></Icon>
