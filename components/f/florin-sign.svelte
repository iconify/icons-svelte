<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iss18acza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="iss18acza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:florin-sign" {...props}></Icon>
