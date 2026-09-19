<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbn1t2yzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zbn1t2yzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-right-from-bracket" {...props}></Icon>
