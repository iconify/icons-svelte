<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-e6webib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-e6webib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playlist-favorite" {...props}></Icon>
