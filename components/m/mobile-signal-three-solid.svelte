<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fucn8nbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fucn8nbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-three-solid" {...props}></Icon>
