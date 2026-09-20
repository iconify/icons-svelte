<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xalh2vdwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xalh2vdwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:arrow-right" {...props}></Icon>
