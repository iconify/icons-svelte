<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppmx33bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":66.61,"height":34.03,"left":249.8,"top":192.24};
const content = `<path class="ppmx33bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:best-western" {...props}></Icon>
