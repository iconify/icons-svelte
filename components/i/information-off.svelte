<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neoczv19k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neoczv19k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:information-off" {...props}></Icon>
