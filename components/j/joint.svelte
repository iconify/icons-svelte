<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgyjh9bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tgyjh9bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:joint" {...props}></Icon>
