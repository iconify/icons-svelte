<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emes4vsnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emes4vsnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:location-point" {...props}></Icon>
