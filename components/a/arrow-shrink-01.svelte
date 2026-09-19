<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drs_rw39z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drs_rw39z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-shrink-01" {...props}></Icon>
