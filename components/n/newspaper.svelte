<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj__e9nfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sj__e9nfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:newspaper" {...props}></Icon>
