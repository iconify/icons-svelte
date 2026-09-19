<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blumpz5xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blumpz5xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-powerpc" {...props}></Icon>
