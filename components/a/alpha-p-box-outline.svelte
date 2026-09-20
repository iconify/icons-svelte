<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3alhbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw3alhbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-p-box-outline" {...props}></Icon>
