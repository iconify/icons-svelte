<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7dfpmfcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x7dfpmfcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuxt" {...props}></Icon>
