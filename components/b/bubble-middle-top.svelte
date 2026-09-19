<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6g1_dr5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j6g1_dr5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bubble-middle-top" {...props}></Icon>
