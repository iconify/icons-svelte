<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bihu32bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bihu32bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lifesaver-fill-16" {...props}></Icon>
