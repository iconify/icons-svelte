<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd85a1byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wd85a1byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:blackberry" {...props}></Icon>
