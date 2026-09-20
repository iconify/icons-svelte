<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seqji0d1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="seqji0d1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:phone" {...props}></Icon>
