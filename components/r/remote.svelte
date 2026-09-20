<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lri53bb8z.css';
import '../../css/d/dj1p29vfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lri53bb8z"/><path class="dj1p29vfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:remote" {...props}></Icon>
