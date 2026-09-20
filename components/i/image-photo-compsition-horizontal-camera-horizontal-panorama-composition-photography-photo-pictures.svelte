<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptypnvblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ptypnvblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-photo-compsition-horizontal-camera-horizontal-panorama-composition-photography-photo-pictures" {...props}></Icon>
