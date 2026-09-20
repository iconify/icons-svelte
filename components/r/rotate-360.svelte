<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/supehpqgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="supehpqgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rotate-360" {...props}></Icon>
