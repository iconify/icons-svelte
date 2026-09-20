<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxs5963tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hxs5963tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:information-11" {...props}></Icon>
