<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fel8-rbzx.css';
import '../../css/g/ghwlb4bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8-rbzx"/><path class="ghwlb4bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-stroke-20" {...props}></Icon>
