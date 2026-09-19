<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw20a1b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw20a1b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:phone-volume" {...props}></Icon>
