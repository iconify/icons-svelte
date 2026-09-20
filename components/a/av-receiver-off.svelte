<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdh-geker.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdh-geker"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:av-receiver-off" {...props}></Icon>
