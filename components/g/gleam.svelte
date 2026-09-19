<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7behsca.css';
import '../../css/a/av17rs-8h.css';
import '../../css/u/uvs-qupzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hn7behsca"/><path class="av17rs-8h"/><path class="uvs-qupzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gleam" {...props}></Icon>
