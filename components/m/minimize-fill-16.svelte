<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc82i_bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vc82i_bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:minimize-fill-16" {...props}></Icon>
