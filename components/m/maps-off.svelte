<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahave22wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahave22wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:maps-off" {...props}></Icon>
