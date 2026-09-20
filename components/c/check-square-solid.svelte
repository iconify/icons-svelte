<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0b3d79qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0b3d79qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-square-solid" {...props}></Icon>
