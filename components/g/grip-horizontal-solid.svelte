<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0n7mtbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0n7mtbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grip-horizontal-solid" {...props}></Icon>
