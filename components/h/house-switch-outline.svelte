<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiih3sb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiih3sb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-switch-outline" {...props}></Icon>
