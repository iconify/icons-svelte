<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ple5b9loz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ple5b9loz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:calibrate" {...props}></Icon>
