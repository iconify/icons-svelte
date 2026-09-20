<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d06s-2bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d06s-2bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:compiling-outline" {...props}></Icon>
