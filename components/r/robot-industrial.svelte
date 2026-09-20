<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q96fchb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q96fchb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-industrial" {...props}></Icon>
