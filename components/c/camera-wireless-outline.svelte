<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at19mqbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at19mqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-wireless-outline" {...props}></Icon>
