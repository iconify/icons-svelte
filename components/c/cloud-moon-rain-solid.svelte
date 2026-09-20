<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jimbkcyht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jimbkcyht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-moon-rain-solid" {...props}></Icon>
