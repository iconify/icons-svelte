<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmhuaub_w.css';
import '../../css/o/ofyg4tbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jmhuaub_w"/><path class="ofyg4tbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:manhole" {...props}></Icon>
