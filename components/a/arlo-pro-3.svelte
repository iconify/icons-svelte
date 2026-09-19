<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylgsnlw_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylgsnlw_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-pro-3" {...props}></Icon>
