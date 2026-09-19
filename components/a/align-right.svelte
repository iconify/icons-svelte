<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agrarus0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agrarus0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:align-right" {...props}></Icon>
