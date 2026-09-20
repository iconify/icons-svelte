<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3p8zp-4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3p8zp-4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:link3-filled" {...props}></Icon>
