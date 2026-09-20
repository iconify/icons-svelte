<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bji8e2b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bji8e2b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:cemetery-14" {...props}></Icon>
