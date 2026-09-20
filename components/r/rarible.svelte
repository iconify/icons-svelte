<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1if_sxyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1if_sxyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rarible" {...props}></Icon>
