<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0n41_jvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0n41_jvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:byd" {...props}></Icon>
