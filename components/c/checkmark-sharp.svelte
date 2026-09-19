<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnax8dbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wnax8dbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkmark-sharp" {...props}></Icon>
