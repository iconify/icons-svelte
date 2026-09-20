<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry-ddxb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry-ddxb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dpay" {...props}></Icon>
