<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i84zo30jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i84zo30jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:duux-360" {...props}></Icon>
