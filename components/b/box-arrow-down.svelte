<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmha0pbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmha0pbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-arrow-down" {...props}></Icon>
