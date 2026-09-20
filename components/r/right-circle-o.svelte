<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_2-cccrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u_2-cccrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:right-circle-o" {...props}></Icon>
