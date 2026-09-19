<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljp-s5bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="ljp-s5bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:drmanhattan" {...props}></Icon>
