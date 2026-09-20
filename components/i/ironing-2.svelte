<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv9cyv-nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv9cyv-nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-2" {...props}></Icon>
