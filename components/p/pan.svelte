<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b49e83bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b49e83bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pan" {...props}></Icon>
