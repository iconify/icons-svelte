<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab51tkfnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":384};
const content = `<path class="ab51tkfnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-line-spacing" {...props}></Icon>
