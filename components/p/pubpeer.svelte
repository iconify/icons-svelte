<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi17097tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="oi17097tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:pubpeer" {...props}></Icon>
