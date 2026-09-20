<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4x19-bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s4x19-bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-photo-composition-vertical-camera-portrait-frame-vertical-composition-photography-photo" {...props}></Icon>
