<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6h057zgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="i6h057zgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:motorcycle" {...props}></Icon>
