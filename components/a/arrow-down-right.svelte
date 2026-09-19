<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugiu9abnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ugiu9abnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-down-right" {...props}></Icon>
