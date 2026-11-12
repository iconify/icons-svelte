<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hspx38ovj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hspx38ovj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clovalink-light" {...props}></Icon>
