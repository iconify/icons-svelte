<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roqoqy64j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roqoqy64j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-right-linear" {...props}></Icon>
