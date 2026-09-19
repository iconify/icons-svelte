<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9nbzj2qc.css';
import '../../css/n/nzs58m68f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="j9nbzj2qc"/><path class="nzs58m68f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:calendar" {...props}></Icon>
