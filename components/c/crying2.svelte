<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1xz4hbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u1xz4hbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:crying2" {...props}></Icon>
