<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3to5ubug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3to5ubug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-on-outline" {...props}></Icon>
