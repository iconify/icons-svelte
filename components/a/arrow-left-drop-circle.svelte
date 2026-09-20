<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad63tmb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad63tmb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-drop-circle" {...props}></Icon>
