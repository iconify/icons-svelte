<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5h-uebpt.css';
import '../../css/q/q74q21bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5h-uebpt"/><path class="q74q21bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:map-boundary-vegetation" {...props}></Icon>
