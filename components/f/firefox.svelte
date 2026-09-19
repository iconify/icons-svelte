<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am0pdubzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1760};
const content = `<path class="am0pdubzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:firefox" {...props}></Icon>
