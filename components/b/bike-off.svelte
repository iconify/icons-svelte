<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw6idgbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw6idgbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bike-off" {...props}></Icon>
