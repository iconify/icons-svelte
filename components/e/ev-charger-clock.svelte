<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3x7blu3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3x7blu3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ev-charger-clock" {...props}></Icon>
