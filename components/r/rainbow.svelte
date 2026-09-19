<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4x4tbcrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="f4x4tbcrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rainbow" {...props}></Icon>
