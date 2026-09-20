<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mia6ae4_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mia6ae4_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cable-car-solid" {...props}></Icon>
