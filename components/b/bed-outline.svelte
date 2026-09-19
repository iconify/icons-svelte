<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpw0hrbqk.css';
import '../../css/z/zdracac6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lpw0hrbqk"/><path class="zdracac6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bed-outline" {...props}></Icon>
