<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8e21kbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e21kbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-fill-round" {...props}></Icon>
