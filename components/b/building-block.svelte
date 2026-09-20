<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvp-jbc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wvp-jbc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:building-block" {...props}></Icon>
