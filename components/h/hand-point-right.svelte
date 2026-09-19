<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6-5tj1wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i6-5tj1wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hand-point-right" {...props}></Icon>
