<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8pk9obri.css';
import '../../css/e/eepyewbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8pk9obri"/><path class="eepyewbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nodule-20-bold" {...props}></Icon>
