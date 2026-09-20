<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs7yqyb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs7yqyb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:notification-off" {...props}></Icon>
