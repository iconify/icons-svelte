<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsvawhb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qsvawhb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:kiss-beam" {...props}></Icon>
