<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzhgg3hpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzhgg3hpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart-down" {...props}></Icon>
