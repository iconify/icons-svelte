<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt5h_1qtq.css';
import '../../css/f/fn8d5vbzf.css';
import '../../css/b/b2th62z3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bt5h_1qtq"/><path class="fn8d5vbzf"/><path class="b2th62z3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-extinguisher-20" {...props}></Icon>
