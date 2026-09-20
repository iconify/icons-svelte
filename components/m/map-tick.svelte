<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7jr9s6ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7jr9s6ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-tick" {...props}></Icon>
