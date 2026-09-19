<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9ki5i3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bw9ki5i3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plus" {...props}></Icon>
