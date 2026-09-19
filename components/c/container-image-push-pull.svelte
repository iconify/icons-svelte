<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_lfmoh3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d_lfmoh3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:container-image-push-pull" {...props}></Icon>
