<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brpb07v6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="brpb07v6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:500px" {...props}></Icon>
