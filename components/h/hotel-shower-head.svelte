<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1r2ibat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kd1r2ibat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-shower-head" {...props}></Icon>
