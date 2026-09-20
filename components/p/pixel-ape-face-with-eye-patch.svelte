<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze91ugbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ze91ugbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-ape-face-with-eye-patch" {...props}></Icon>
