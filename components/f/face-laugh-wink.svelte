<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3h7__b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3h7__b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-laugh-wink" {...props}></Icon>
