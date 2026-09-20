<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0vmalbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0vmalbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-arrow-right-outline" {...props}></Icon>
