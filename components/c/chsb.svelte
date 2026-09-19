<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm572wv6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hm572wv6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:chsb" {...props}></Icon>
