<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ion_h5bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ion_h5bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lily-xl-alt" {...props}></Icon>
