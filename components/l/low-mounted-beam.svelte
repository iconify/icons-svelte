<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa865izzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wa865izzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:low-mounted-beam" {...props}></Icon>
