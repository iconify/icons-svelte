<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3wmuabkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3wmuabkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-week" {...props}></Icon>
