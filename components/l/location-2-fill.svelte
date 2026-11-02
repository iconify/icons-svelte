<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2qv7ttnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2qv7ttnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-2-fill" {...props}></Icon>
