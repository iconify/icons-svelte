<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vju6l6brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vju6l6brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:geofence" {...props}></Icon>
