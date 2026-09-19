<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd_y6vbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":959};
const content = `<path class="rd_y6vbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:diethree" {...props}></Icon>
