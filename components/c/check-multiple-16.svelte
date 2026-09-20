<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1s0wnp6w.css';
import '../../css/z/zqzhegyvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q1s0wnp6w"/><path class="zqzhegyvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:check-multiple-16" {...props}></Icon>
