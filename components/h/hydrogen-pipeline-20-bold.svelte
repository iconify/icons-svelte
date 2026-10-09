<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx-_djyyn.css';
import '../../css/p/pci-8zxna.css';
import '../../css/j/j83cdtwkl.css';
import '../../css/z/z2lgmebod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lx-_djyyn"/><path class="pci-8zxna"/><path class="j83cdtwkl"/><path class="z2lgmebod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-pipeline-20-bold" {...props}></Icon>
