<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-600_bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-600_bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-8" {...props}></Icon>
