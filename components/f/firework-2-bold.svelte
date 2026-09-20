<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__ivvbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k__ivvbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:firework-2-bold" {...props}></Icon>
