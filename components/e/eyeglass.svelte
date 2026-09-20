<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4adif_2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c4adif_2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:eyeglass" {...props}></Icon>
