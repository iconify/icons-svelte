<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdtrcfbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdtrcfbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-right-linear" {...props}></Icon>
