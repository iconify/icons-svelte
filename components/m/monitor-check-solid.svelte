<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbt2vcxfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbt2vcxfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-check-solid" {...props}></Icon>
