<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxwu6fq3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxwu6fq3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:red-hat-lightspeed-light" {...props}></Icon>
