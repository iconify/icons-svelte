<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofzjtmbpe.css';
import '../../css/r/rm_v3ccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ofzjtmbpe"/><path class="rm_v3ccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-to-line-48" {...props}></Icon>
