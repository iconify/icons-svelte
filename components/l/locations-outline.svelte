<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxg82f72d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg82f72d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:locations-outline" {...props}></Icon>
