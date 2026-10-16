<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3j2ttbri.css';
import '../../css/w/w0ahlnbjy.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o3j2ttbri"/><path class="w0ahlnbjy"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:foundry-ladle-20" {...props}></Icon>
