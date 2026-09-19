<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lulf7bc2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lulf7bc2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-laugh-wink" {...props}></Icon>
