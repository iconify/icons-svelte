<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flmdk8oav.css';
import '../../css/t/t-h0v1sjr.css';
import '../../css/a/ajt2cbbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="flmdk8oav"/><path class="t-h0v1sjr"/><path class="ajt2cbbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:belarus" {...props}></Icon>
