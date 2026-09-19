<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_z5v4b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_z5v4b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lg-aircon" {...props}></Icon>
