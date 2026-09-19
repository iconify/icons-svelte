<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkqps8bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gkqps8bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bacteria" {...props}></Icon>
