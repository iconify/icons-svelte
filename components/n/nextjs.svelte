<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms2y87bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ms2y87bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nextjs" {...props}></Icon>
