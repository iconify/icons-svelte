<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrvsvkmmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrvsvkmmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloudy" {...props}></Icon>
