<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m27p55t_c.css';
import '../../css/g/gqu4bebvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m27p55t_c"/><path class="gqu4bebvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nasm" {...props}></Icon>
