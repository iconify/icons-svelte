<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwz6_x2lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mwz6_x2lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dblp" {...props}></Icon>
