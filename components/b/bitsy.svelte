<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsx06-b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsx06-b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitsy" {...props}></Icon>
