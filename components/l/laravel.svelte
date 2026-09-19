<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpgg-p1ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tpgg-p1ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:laravel" {...props}></Icon>
