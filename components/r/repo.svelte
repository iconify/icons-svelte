<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z29616bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="z29616bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo" {...props}></Icon>
