<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eby38zzef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eby38zzef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:cube-unfolded" {...props}></Icon>
