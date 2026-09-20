<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8steec1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8steec1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:navigation-filled" {...props}></Icon>
