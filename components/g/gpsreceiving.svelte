<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3x8ayb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="p3x8ayb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:gpsreceiving" {...props}></Icon>
