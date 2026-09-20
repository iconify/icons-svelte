<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbkr5uppu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbkr5uppu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-d-circle-outline" {...props}></Icon>
