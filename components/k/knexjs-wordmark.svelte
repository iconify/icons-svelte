<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kunthyb0f.css';
import '../../css/b/bzghj2btg.css';
import '../../css/d/dph_j-9vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kunthyb0f"/><path class="bzghj2btg"/><path class="dph_j-9vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:knexjs-wordmark" {...props}></Icon>
