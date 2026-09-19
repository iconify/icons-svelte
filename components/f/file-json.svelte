<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik5-7ezyb.css';
import '../../css/r/rvju-3bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik5-7ezyb"/><path class="rvju-3bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-json" {...props}></Icon>
