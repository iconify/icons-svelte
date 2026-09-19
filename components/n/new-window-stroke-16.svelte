<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbka6eb7h.css';
import '../../css/p/piht5gbxt.css';
import '../../css/k/knkpb5bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nbka6eb7h"/><path class="piht5gbxt"/><path class="knkpb5bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:new-window-stroke-16" {...props}></Icon>
