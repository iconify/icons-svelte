<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_vqb6ra.css';
import '../../css/u/ufnji5p1c.css';
import '../../css/x/xec2qh1xw.css';
import '../../css/k/k9hgj4wof.css';
import '../../css/y/yj-l38s9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hf_vqb6ra"/><path class="ufnji5p1c"/><path class="xec2qh1xw"/><path class="k9hgj4wof"/><path class="yj-l38s9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opencl" {...props}></Icon>
