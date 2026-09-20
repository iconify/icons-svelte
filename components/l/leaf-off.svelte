<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yghw3sbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yghw3sbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:leaf-off" {...props}></Icon>
