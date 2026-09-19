<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzfbw_33j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzfbw_33j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:address-book" {...props}></Icon>
