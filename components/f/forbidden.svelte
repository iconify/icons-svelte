<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibmv57b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ibmv57b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:forbidden" {...props}></Icon>
