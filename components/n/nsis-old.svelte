<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0i8fc4rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0i8fc4rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nsis-old" {...props}></Icon>
