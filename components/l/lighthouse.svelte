<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt6nh0b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt6nh0b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lighthouse" {...props}></Icon>
