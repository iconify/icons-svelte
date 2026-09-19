<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw8_z_2nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="iw8_z_2nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:circle-arrow-right" {...props}></Icon>
