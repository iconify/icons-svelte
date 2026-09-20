<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igtivtbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igtivtbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cctv-off" {...props}></Icon>
