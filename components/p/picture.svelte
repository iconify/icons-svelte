<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7o2i6b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a7o2i6b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:picture" {...props}></Icon>
