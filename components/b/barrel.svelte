<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_awcdqqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":833,"height":1024};
const content = `<path class="j_awcdqqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:barrel" {...props}></Icon>
