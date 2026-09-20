<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njivm9bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njivm9bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-scooter" {...props}></Icon>
