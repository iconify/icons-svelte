<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn9u4nb1b.css';
import '../../css/r/r_rs3to2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn9u4nb1b"/><path class="r_rs3to2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bomb" {...props}></Icon>
