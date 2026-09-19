<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_u-ykb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x_u-ykb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-image" {...props}></Icon>
