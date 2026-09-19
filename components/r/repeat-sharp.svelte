<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hic_gdiic.css';
import '../../css/p/pohcxhbiw.css';
import '../../css/r/r84b_cbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hic_gdiic"/><path class="pohcxhbiw"/><path class="r84b_cbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:repeat-sharp" {...props}></Icon>
