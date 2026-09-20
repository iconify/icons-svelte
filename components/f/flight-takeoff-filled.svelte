<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihagv-bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihagv-bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flight-takeoff-filled" {...props}></Icon>
