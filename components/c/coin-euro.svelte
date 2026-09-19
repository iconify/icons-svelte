<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpcp248iu.css';
import '../../css/f/frl5hnbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dpcp248iu"/><path class="frl5hnbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:coin-euro" {...props}></Icon>
