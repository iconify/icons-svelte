<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxf281bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lxf281bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ads" {...props}></Icon>
