<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt8f-3eoh.css';
import '../../css/q/qruqcigga.css';
import '../../css/q/qll7tub0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="qruqcigga"/><path class="qll7tub0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-cog-20-bold" {...props}></Icon>
