<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrtqw4bir.css';
import '../../css/c/cat4-0bmn.css';
import '../../css/k/k-_vm5b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lrtqw4bir"/><path class="cat4-0bmn"/><path class="k-_vm5b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:linuxmint" {...props}></Icon>
