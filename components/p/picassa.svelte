<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4y_u1bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="r4y_u1bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:picassa" {...props}></Icon>
