<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0t096bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0t096bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:recipe" {...props}></Icon>
