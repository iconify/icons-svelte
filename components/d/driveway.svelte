<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_2nwb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9_2nwb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:driveway" {...props}></Icon>
