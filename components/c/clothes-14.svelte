<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbh0f59lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lbh0f59lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:clothes-14" {...props}></Icon>
