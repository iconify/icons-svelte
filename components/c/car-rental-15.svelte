<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxyl2pbba.css';
import '../../css/m/m-7so2bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wxyl2pbba"/><path class="m-7so2bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-rental-15" {...props}></Icon>
