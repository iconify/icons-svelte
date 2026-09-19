<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t12a6fb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t12a6fb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-laugh-squint" {...props}></Icon>
