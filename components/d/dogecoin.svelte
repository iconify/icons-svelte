<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r20zsnx-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r20zsnx-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dogecoin" {...props}></Icon>
