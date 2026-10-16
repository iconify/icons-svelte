<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7m7xy44u.css';
import '../../css/t/t5jb97bqd.css';
import '../../css/c/cxsgvgbjp.css';
import '../../css/k/k413g3b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j7m7xy44u"/><path class="t5jb97bqd"/><path class="cxsgvgbjp"/><path class="k413g3b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightning-protection-20-bold" {...props}></Icon>
