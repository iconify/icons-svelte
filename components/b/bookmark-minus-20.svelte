<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2kktob7s.css';
import '../../css/p/puz5jibvr.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z2kktob7s"/><path class="puz5jibvr"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-minus-20" {...props}></Icon>
