<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6fxnxb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n6fxnxb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:css3" {...props}></Icon>
