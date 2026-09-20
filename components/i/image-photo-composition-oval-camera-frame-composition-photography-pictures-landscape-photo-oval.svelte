<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3___fhtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b3___fhtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-photo-composition-oval-camera-frame-composition-photography-pictures-landscape-photo-oval" {...props}></Icon>
