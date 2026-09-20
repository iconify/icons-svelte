<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muunylb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="muunylb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:printer" {...props}></Icon>
