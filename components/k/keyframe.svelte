<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0p0e8b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0p0e8b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:keyframe" {...props}></Icon>
