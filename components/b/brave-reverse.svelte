<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtl_iywhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jtl_iywhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:brave-reverse" {...props}></Icon>
