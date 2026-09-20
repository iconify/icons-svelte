<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi7yh323x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi7yh323x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-3-fill" {...props}></Icon>
