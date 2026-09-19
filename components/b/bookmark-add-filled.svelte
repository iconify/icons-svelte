<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg9bm_ucs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9bm_ucs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bookmark-add-filled" {...props}></Icon>
