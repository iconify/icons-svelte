<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6epwbbxl.css';
import '../../css/f/f92h2vb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6epwbbxl"/><path class="f92h2vb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biochar-20" {...props}></Icon>
